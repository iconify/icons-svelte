<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnqjm83et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mnqjm83et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:status-circle-exclamation" {...props}></Icon>
