<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9d51b_-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v9d51b_-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:snowflake-1" {...props}></Icon>
