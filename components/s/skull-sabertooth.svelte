<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukd08s7uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ukd08s7uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:skull-sabertooth" {...props}></Icon>
