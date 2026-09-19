<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp93yxbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vp93yxbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:thorny-vine" {...props}></Icon>
