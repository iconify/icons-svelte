<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo2ghhbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lo2ghhbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:skull-staff" {...props}></Icon>
