<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7io4dvsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d7io4dvsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:x-pack" {...props}></Icon>
