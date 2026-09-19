<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg8mi0v1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fg8mi0v1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shield" {...props}></Icon>
