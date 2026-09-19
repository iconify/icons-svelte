<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lffz6_2ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lffz6_2ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:view-boards" {...props}></Icon>
