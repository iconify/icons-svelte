<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlv-olo2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xlv-olo2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:sparkfun" {...props}></Icon>
