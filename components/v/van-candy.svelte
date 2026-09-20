<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2nyjac-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2nyjac-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:van-candy" {...props}></Icon>
