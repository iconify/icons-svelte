<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk_qalbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="fk_qalbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sort-alphabetical-ascending-thin" {...props}></Icon>
