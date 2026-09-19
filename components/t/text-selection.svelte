<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bicjs882a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bicjs882a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-selection" {...props}></Icon>
