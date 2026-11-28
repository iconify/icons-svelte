<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/relh8ld0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="relh8ld0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:workflow" {...props}></Icon>
