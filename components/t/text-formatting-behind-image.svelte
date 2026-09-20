<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebd8srt4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ebd8srt4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:text-formatting-behind-image" {...props}></Icon>
