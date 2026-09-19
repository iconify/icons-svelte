<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emmbnebwc.css';
import '../../css/p/pu8y5lb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="emmbnebwc"/><path class="pu8y5lb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:train-profile" {...props}></Icon>
