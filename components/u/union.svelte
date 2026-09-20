<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb8khkb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb8khkb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:union" {...props}></Icon>
