<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grfi6tbpu.css';
import '../../css/r/rwxu_6bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="grfi6tbpu"/><path class="rwxu_6bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sunshine-dark" {...props}></Icon>
