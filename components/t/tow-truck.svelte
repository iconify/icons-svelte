<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmdj_8bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cmdj_8bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tow-truck" {...props}></Icon>
