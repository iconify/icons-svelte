<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0x5bsqdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="f0x5bsqdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:tennis" {...props}></Icon>
