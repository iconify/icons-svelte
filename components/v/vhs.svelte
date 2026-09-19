<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhiuo3b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dhiuo3b4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:vhs" {...props}></Icon>
