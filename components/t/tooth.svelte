<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt_agpben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zt_agpben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tooth" {...props}></Icon>
