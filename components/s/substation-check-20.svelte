<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqvp7v6ug.css';
import '../../css/j/j02yjqo5b.css';
import '../../css/y/y0aff0bve.css';
import '../../css/q/qh3-d7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fqvp7v6ug"/><path class="j02yjqo5b"/><path class="y0aff0bve"/><path class="qh3-d7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:substation-check-20" {...props}></Icon>
