<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjom0ukgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cjom0ukgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sun-priest" {...props}></Icon>
