<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn11h8yys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bn11h8yys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:winter-gloves" {...props}></Icon>
