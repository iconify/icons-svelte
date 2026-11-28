<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gknsb7b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gknsb7b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sidebar-simple-close-fill" {...props}></Icon>
