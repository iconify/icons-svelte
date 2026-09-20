<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnjk4qv4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="vnjk4qv4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:train-station" {...props}></Icon>
