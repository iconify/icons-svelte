<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlyym_dwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qlyym_dwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:tram" {...props}></Icon>
