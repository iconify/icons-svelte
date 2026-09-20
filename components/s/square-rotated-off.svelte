<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf3rk1hgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf3rk1hgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rotated-off" {...props}></Icon>
