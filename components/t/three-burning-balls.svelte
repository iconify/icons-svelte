<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n11niyb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n11niyb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:three-burning-balls" {...props}></Icon>
