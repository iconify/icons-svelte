<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnht8g86b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dnht8g86b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-md-solid" {...props}></Icon>
