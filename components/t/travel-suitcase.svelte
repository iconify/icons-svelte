<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqbzp98xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oqbzp98xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:travel-suitcase" {...props}></Icon>
