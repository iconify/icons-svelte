<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5votw93x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":302,"height":512};
const content = `<path class="i5votw93x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:wine" {...props}></Icon>
