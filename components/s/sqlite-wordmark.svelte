<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by4kbj5ev.css';
import '../../css/h/hhg6y4bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="by4kbj5ev"/><path class="hhg6y4bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:sqlite-wordmark" {...props}></Icon>
