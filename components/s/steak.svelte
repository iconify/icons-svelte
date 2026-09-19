<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgww5qb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tgww5qb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:steak" {...props}></Icon>
