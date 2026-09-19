<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpletlpsy.css';
import '../../css/t/teyp2chse.css';
import '../../css/e/e29_vw92i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dpletlpsy"/><path class="teyp2chse"/><path class="e29_vw92i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:tether" {...props}></Icon>
