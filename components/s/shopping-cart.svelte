<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsdwxr0qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nsdwxr0qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shopping-cart" {...props}></Icon>
