<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3ti3obmt.css';
import '../../css/m/mef0poblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="k3ti3obmt"/><path class="mef0poblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:wavy-dash" {...props}></Icon>
