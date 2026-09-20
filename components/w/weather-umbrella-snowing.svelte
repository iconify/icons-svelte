<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc17hactt.css';
import '../../css/b/bo_dldbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yc17hactt"/><path class="bo_dldbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:weather-umbrella-snowing" {...props}></Icon>
