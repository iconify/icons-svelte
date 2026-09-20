<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m89ik2bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m89ik2bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sound-quiet" {...props}></Icon>
