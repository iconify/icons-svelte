<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zld1hq7zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zld1hq7zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shirt-solid" {...props}></Icon>
