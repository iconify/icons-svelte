<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3n--bptp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h3n--bptp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:satellite-dish" {...props}></Icon>
