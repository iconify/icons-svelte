<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6wtytb_v.css';
import '../../css/p/phf4gf3fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i6wtytb_v"/><path class="phf4gf3fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sendgrid-dark" {...props}></Icon>
