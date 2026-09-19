<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fccpd3bnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fccpd3bnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:web-spit" {...props}></Icon>
