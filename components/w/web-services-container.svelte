<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsrzeq-ig.css';
import '../../css/t/tz_5mvbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hsrzeq-ig"/><path class="tz_5mvbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:web-services-container" {...props}></Icon>
