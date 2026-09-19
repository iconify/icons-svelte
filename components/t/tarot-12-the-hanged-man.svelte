<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdguj2hdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jdguj2hdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-12-the-hanged-man" {...props}></Icon>
