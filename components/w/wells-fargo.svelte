<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyh0s5bvl.css';
import '../../css/c/ciel5gbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dyh0s5bvl"/><path class="ciel5gbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wells-fargo" {...props}></Icon>
