<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/n5g3q8bii.css';
import '../../css/n/ned4scb6o.css';
import '../../css/o/ohvlkxycg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n5g3q8bii"/><path class="ned4scb6o"/><path class="ohvlkxycg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:universe" {...props}></Icon>
