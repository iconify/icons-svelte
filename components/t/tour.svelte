<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpiteb51d.css';
import '../../css/v/v23tyc59y.css';
import '../../css/b/bfox5ubnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qpiteb51d"/><circle class="v23tyc59y"/><path class="bfox5ubnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tour" {...props}></Icon>
