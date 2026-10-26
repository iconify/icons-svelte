<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6yd4ubmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g6yd4ubmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:ruler" {...props}></Icon>
