<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp_9pbj6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pp_9pbj6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:unbalanced" {...props}></Icon>
