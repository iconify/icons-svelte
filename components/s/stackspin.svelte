<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf-ixubsz.css';
import '../../css/r/r8xkjtbka.css';
import '../../css/p/pnqtkcbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mf-ixubsz"/><path class="r8xkjtbka"/><path class="pnqtkcbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stackspin" {...props}></Icon>
