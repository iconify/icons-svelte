<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7luxtfip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f7luxtfip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:thorned-arrow" {...props}></Icon>
