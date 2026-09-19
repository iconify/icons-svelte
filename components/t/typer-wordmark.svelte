<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx_6q807q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yx_6q807q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:typer-wordmark" {...props}></Icon>
