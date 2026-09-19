<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk8c-26km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xk8c-26km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:small-dash-outlined" {...props}></Icon>
