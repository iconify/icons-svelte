<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r55ny5bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="r55ny5bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tooltip-below-help" {...props}></Icon>
