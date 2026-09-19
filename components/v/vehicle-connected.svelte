<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb4s33bah.css';
import '../../css/r/rtki51b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kb4s33bah"/><path class="rtki51b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:vehicle-connected" {...props}></Icon>
