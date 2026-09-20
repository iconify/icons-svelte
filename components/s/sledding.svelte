<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io_ltac6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="io_ltac6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:sledding" {...props}></Icon>
