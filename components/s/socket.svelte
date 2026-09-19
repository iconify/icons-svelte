<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak-sz5dbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ak-sz5dbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:socket" {...props}></Icon>
