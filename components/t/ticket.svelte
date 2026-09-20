<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju64m7nre.css';
import '../../css/g/gm7gmzfit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ju64m7nre"/><path class="gm7gmzfit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:ticket" {...props}></Icon>
