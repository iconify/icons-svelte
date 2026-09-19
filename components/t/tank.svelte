<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz-_zlbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mz-_zlbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tank" {...props}></Icon>
