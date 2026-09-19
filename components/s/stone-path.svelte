<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q05doo8qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q05doo8qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stone-path" {...props}></Icon>
