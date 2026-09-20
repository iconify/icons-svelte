<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5owyxbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k5owyxbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sidero-talos-light" {...props}></Icon>
