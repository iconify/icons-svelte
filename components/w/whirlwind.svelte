<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff0tn4i0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ff0tn4i0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:whirlwind" {...props}></Icon>
