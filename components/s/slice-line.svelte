<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb20qb1lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb20qb1lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:slice-line" {...props}></Icon>
