<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbjjpv75l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hbjjpv75l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:suitcase" {...props}></Icon>
