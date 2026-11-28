<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phngu9b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="phngu9b5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:turtle" {...props}></Icon>
