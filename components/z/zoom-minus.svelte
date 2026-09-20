<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcrey0bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qcrey0bhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:zoom-minus" {...props}></Icon>
