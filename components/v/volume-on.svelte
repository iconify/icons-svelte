<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oewbiur4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2016,"height":1728};
const content = `<path class="oewbiur4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:volume-on" {...props}></Icon>
