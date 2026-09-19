<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boazfbb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="boazfbb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tides" {...props}></Icon>
