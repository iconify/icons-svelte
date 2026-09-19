<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8g3psbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s8g3psbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:turtle" {...props}></Icon>
