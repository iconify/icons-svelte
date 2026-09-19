<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rihk17bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rihk17bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:tex" {...props}></Icon>
