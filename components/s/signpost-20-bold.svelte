<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a60pyzb1b.css';
import '../../css/e/ejvwyfy7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a60pyzb1b"/><path class="ejvwyfy7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signpost-20-bold" {...props}></Icon>
