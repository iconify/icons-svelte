<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds7t43jyo.css';
import '../../css/e/e3ss8accz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds7t43jyo"/><path class="e3ss8accz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xdc" {...props}></Icon>
