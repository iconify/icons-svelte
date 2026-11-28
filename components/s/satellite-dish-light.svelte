<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsp35ou_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="lsp35ou_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:satellite-dish-light" {...props}></Icon>
