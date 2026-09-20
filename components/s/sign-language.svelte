<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wom0nulsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="wom0nulsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:sign-language" {...props}></Icon>
