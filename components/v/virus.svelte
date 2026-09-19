<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5jdxi8fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h5jdxi8fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:virus" {...props}></Icon>
