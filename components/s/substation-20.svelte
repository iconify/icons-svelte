<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg06y9bau.css';
import '../../css/j/j02yjqo5b.css';
import '../../css/v/vxu1d29jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hg06y9bau"/><path class="j02yjqo5b"/><path class="vxu1d29jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:substation-20" {...props}></Icon>
