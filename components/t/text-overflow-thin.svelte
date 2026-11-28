<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp-cyjppm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="fp-cyjppm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:text-overflow-thin" {...props}></Icon>
