<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2ibnsbfx.css';
import '../../css/k/kb4_7ccic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q2ibnsbfx"/><path class="kb4_7ccic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:swagger" {...props}></Icon>
