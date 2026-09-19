<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6mk1rb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v6mk1rb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stack" {...props}></Icon>
