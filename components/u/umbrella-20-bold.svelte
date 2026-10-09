<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qodg3fqvb.css';
import '../../css/o/o32ailbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qodg3fqvb"/><path class="o32ailbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:umbrella-20-bold" {...props}></Icon>
