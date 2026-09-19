<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gblm57xqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gblm57xqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:zat-gun" {...props}></Icon>
