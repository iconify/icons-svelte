<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azaf2ubzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="azaf2ubzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:subway-station" {...props}></Icon>
