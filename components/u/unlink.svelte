<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tovlsf9tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tovlsf9tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:unlink" {...props}></Icon>
