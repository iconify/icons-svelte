<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9r0s9wjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="c9r0s9wjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:zoom-out-alt" {...props}></Icon>
