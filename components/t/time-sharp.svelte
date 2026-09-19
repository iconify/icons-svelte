<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mufx9zvgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mufx9zvgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:time-sharp" {...props}></Icon>
