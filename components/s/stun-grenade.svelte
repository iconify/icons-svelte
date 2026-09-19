<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckxui5r1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ckxui5r1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stun-grenade" {...props}></Icon>
