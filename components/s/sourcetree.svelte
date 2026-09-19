<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg3ny2g5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="eg3ny2g5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:sourcetree" {...props}></Icon>
