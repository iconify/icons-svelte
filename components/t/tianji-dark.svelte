<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx10v2n2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sx10v2n2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tianji-dark" {...props}></Icon>
