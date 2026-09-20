<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt9f0cb0i.css';
import '../../css/b/brrdf9bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="lt9f0cb0i"/><path class="brrdf9bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:spoon" {...props}></Icon>
