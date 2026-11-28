<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c__d53b9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c__d53b9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:tags-fill" {...props}></Icon>
