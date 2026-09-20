<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hetltv1hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="hetltv1hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:snow-shoeing" {...props}></Icon>
