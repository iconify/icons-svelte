<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmyfs8bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rmyfs8bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:wifi-outlined" {...props}></Icon>
