<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2i0bqbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="w2i0bqbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sidebar-simple-bottom-thin" {...props}></Icon>
