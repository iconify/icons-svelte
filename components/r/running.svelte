<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfd-gok6c.css';
import '../../css/g/g369r0bza.css';
import '../../css/f/flo-2gl9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wfd-gok6c"/><path class="g369r0bza"/><path class="flo-2gl9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:running" {...props}></Icon>
