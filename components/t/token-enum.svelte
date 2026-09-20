<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjkubb39r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sjkubb39r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-enum" {...props}></Icon>
