<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh62jbbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uh62jbbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vyper" {...props}></Icon>
