<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehrz3ubhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ehrz3ubhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:session-border-control" {...props}></Icon>
