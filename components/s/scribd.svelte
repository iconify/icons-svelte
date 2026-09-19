<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-pliwn4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d-pliwn4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:scribd" {...props}></Icon>
