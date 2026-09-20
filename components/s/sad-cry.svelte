<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpozg-01u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lpozg-01u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sad-cry" {...props}></Icon>
