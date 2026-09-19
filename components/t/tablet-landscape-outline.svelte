<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv4wt1bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect transform="rotate(-90 256 256)" class="kv4wt1bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:tablet-landscape-outline" {...props}></Icon>
