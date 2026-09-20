<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgqcqbibj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jgqcqbibj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:socialhome-dark" {...props}></Icon>
