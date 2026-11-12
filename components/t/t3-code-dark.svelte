<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guq7mxbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="guq7mxbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:t3-code-dark" {...props}></Icon>
