<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_c3n_rwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k_c3n_rwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:storage-rental" {...props}></Icon>
