<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv7g_mxtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lv7g_mxtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vitepress-light" {...props}></Icon>
