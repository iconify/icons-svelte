<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzrv9qbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hzrv9qbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tilde-large" {...props}></Icon>
