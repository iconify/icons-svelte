<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdqml2b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jdqml2b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:viking-helmet" {...props}></Icon>
