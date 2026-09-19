<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s64jidcwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s64jidcwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:valley" {...props}></Icon>
