<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m00o5vb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m00o5vb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:seq-light" {...props}></Icon>
