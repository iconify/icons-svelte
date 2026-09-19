<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb96msy1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lb96msy1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:vertical-banner" {...props}></Icon>
