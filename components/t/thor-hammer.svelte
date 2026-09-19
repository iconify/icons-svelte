<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb8s-v9gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jb8s-v9gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:thor-hammer" {...props}></Icon>
