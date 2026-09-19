<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e164d41mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e164d41mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:volume-low-sharp" {...props}></Icon>
