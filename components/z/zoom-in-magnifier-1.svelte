<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq-ess6cm.css';
import '../../css/h/h5ci0qb1w.css';
import '../../css/f/fd5oc7b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq-ess6cm"/><path class="h5ci0qb1w"/><path class="fd5oc7b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:zoom-in-magnifier-1" {...props}></Icon>
