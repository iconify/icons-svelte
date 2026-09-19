<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq-gx3bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cq-gx3bpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:whitemediumsmallsquare" {...props}></Icon>
