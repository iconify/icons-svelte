<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i186x-vtx.css';
import '../../css/i/ivau6ccrv.css';
import '../../css/v/vjtndybvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i186x-vtx"/><path class="ivau6ccrv"/><path class="vjtndybvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:vlc" {...props}></Icon>
