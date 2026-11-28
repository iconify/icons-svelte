<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdfu06-uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cdfu06-uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sort-alphabetical-ascending-bold" {...props}></Icon>
