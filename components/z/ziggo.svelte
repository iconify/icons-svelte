<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_95w9bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_95w9bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ziggo" {...props}></Icon>
