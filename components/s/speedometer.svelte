<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji_aadxel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ji_aadxel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:speedometer" {...props}></Icon>
