<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffo8hqbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ffo8hqbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:ticket" {...props}></Icon>
