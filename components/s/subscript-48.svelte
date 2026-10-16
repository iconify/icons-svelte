<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da8ahcs8d.css';
import '../../css/f/fhiwyn5qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="da8ahcs8d"/><path class="fhiwyn5qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:subscript-48" {...props}></Icon>
