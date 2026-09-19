<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ael58jbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ael58jbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-intersect" {...props}></Icon>
