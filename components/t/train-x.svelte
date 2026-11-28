<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd3fyqbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd3fyqbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:train-x" {...props}></Icon>
