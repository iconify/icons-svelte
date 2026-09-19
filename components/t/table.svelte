<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s221sp3wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s221sp3wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:table" {...props}></Icon>
