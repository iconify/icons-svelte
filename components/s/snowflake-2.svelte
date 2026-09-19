<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbcc_bcyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zbcc_bcyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:snowflake-2" {...props}></Icon>
