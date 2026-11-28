<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du20kcbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="du20kcbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sort-alphabetical-ascending-fill" {...props}></Icon>
