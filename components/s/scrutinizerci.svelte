<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hokl__b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hokl__b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:scrutinizerci" {...props}></Icon>
