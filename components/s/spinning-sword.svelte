<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp11r-b8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mp11r-b8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spinning-sword" {...props}></Icon>
