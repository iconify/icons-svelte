<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlei2-bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jlei2-bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:tools" {...props}></Icon>
