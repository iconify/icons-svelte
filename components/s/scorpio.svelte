<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_5pqyzxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_5pqyzxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:scorpio" {...props}></Icon>
