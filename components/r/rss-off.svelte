<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skx0vxbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skx0vxbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rss-off" {...props}></Icon>
