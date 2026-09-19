<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1n7stbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f1n7stbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:traffic-cone" {...props}></Icon>
