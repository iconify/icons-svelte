<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2y5ycc9l.css';
import '../../css/u/ujx7g2v4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="y2y5ycc9l"/><path class="ujx7g2v4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:start" {...props}></Icon>
