<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd8or5nik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sd8or5nik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:unlock-outline" {...props}></Icon>
