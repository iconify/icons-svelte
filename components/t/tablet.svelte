<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0zfj_7yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d0zfj_7yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tablet" {...props}></Icon>
