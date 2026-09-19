<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_cxxpbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_cxxpbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rss-unlocked" {...props}></Icon>
