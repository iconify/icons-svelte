<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsbt4b50t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zsbt4b50t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:time-dynamite" {...props}></Icon>
