<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8nq0acyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8nq0acyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:trade" {...props}></Icon>
