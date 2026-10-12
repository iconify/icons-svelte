<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqvp7v6ug.css';
import '../../css/j/j02yjqo5b.css';
import '../../css/y/y0aff0bve.css';
import '../../css/l/lzmnrrp8b.css';
import '../../css/m/mxz5qbb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fqvp7v6ug"/><path class="j02yjqo5b"/><path class="y0aff0bve"/><path class="lzmnrrp8b"/><path class="mxz5qbb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:substation-x-20" {...props}></Icon>
