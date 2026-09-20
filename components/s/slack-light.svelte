<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptpoay_pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ptpoay_pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:slack-light" {...props}></Icon>
