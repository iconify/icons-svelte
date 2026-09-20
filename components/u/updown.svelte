<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aco_-tbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="aco_-tbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:updown" {...props}></Icon>
