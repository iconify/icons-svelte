<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-l-fackh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j-l-fackh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sliced-sausage" {...props}></Icon>
