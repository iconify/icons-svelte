<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr6xyx3_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gr6xyx3_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:unity" {...props}></Icon>
