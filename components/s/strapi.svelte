<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l76imif0i.css';
import '../../css/e/e9w-z4r_y.css';
import '../../css/c/c06h_s1-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l76imif0i"/><path class="e9w-z4r_y"/><path class="c06h_s1-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:strapi" {...props}></Icon>
