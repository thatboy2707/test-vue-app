<template>
    <div id="PropertyAddresses">
        <table>
            <thead>
            <tr>
                <th>Employee name</th>
                <th>Employee email</th>
            </tr>
            </thead>
            <tbody>
            <tr>
                <td>Richard Hendricks</td>
                <td>richard@piedpiper.com</td>
            </tr>
            <tr>
                <td>Bertram Gilfoyle</td>
                <td>gilfoyle@piedpiper.com</td>
            </tr>
            <tr>
                <td>Dinesh Chugtai</td>
                <td>dinesh@piedpiper.com</td>
            </tr>
            </tbody>
        </table>
    </div>
</template>

<script>
    export default {
        name: 'PropertyAddresses',
        props: {
            msg: String
        }
    }
</script>
<style scoped></style>
