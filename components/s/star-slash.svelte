<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnit4maum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cnit4maum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:star-slash" {...props}></Icon>
