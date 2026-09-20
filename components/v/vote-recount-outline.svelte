<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdkbzpbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdkbzpbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vote-recount-outline" {...props}></Icon>
