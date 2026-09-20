<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1--uke8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y1--uke8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:teamspeak" {...props}></Icon>
