<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cggeh_puv.css';
import '../../css/l/lx9txg18g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="cggeh_puv"/><path class="lx9txg18g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:small-blue-diamond" {...props}></Icon>
