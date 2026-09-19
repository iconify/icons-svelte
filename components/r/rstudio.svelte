<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_32mb0cg.css';
import '../../css/q/qsse9abge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q_32mb0cg"/><path class="qsse9abge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:rstudio" {...props}></Icon>
