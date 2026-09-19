<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_48uzbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_48uzbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rss-connected-01" {...props}></Icon>
