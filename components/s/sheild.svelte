<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_ep0bbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="n_ep0bbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:sheild" {...props}></Icon>
