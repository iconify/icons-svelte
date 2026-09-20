<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsww-ujmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="qsww-ujmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:wheelchair" {...props}></Icon>
