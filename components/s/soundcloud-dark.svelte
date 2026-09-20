<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9l9obcqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":75,"height":33.51};
const content = `<path class="s9l9obcqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:soundcloud-dark" {...props}></Icon>
