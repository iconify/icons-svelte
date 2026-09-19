<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at9p0p48i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="at9p0p48i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:volume-mute" {...props}></Icon>
