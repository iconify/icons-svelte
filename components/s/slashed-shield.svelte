<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k78kfq9cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k78kfq9cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:slashed-shield" {...props}></Icon>
