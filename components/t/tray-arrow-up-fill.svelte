<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r34fhinxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="r34fhinxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tray-arrow-up-fill" {...props}></Icon>
