<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jssoprxmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="star-outline"><path class="Vector jssoprxmo" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:star-outline" {...props}></Icon>
