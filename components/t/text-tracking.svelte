<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldh1uqbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ldh1uqbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-tracking" {...props}></Icon>
