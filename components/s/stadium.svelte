<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6byiab5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="t6byiab5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:stadium" {...props}></Icon>
