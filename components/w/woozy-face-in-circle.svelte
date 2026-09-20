<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz30cqbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jz30cqbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:woozy-face-in-circle" {...props}></Icon>
