<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzj-a2bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bzj-a2bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spell-book" {...props}></Icon>
