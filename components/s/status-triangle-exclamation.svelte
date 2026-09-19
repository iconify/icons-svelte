<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy1lhl79c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gy1lhl79c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:status-triangle-exclamation" {...props}></Icon>
