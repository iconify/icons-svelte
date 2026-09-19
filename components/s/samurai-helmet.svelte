<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9mrjx-_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v9mrjx-_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:samurai-helmet" {...props}></Icon>
