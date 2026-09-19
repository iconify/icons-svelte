<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqcrtybxv.css';
import '../../css/w/wr6o5qbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qqcrtybxv"/><path class="wr6o5qbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shape-exclude" {...props}></Icon>
