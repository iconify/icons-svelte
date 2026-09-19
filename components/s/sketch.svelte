<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmvbvqbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmvbvqbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:sketch" {...props}></Icon>
