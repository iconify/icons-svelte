<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgt0q_kas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kgt0q_kas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:smore-newsletter-light" {...props}></Icon>
