<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxa_hyp1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nxa_hyp1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:t3-code-light" {...props}></Icon>
