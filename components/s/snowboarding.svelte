<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfy3eubrn.css';
import '../../css/h/hoeze_b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<ellipse class="hfy3eubrn"/><path class="hoeze_b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:snowboarding" {...props}></Icon>
