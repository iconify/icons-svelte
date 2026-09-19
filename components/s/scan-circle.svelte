<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-0ypccvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k-0ypccvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:scan-circle" {...props}></Icon>
