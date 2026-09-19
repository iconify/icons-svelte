<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bieq96bfh.css';
import '../../css/i/iyk4v5bbj.css';
import '../../css/t/tz_5mvbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bieq96bfh"/><path class="iyk4v5bbj"/><path class="tz_5mvbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:web-services-definition" {...props}></Icon>
