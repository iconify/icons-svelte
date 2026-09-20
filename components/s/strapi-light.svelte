<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtf41p-9o.css';
import '../../css/b/bynye9btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qtf41p-9o"/><path class="bynye9btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:strapi-light" {...props}></Icon>
