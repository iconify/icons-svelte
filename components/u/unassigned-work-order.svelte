<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stiiw_f7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="stiiw_f7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:unassigned-work-order" {...props}></Icon>
