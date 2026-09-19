<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytjf0pb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ytjf0pb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tied-scroll" {...props}></Icon>
