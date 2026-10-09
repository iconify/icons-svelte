<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_l85o6fg.css';
import '../../css/d/drwzrccpo.css';
import '../../css/c/cgyi4tt_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i_l85o6fg"/><path class="drwzrccpo"/><path class="cgyi4tt_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:steel-mill-48" {...props}></Icon>
