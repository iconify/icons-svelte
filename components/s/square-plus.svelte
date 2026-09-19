<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rij442pdg.css';
import '../../css/m/mbirz4byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rij442pdg"/><path class="mbirz4byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:square-plus" {...props}></Icon>
