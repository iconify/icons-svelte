<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8hkjl3zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j8hkjl3zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:triorb" {...props}></Icon>
