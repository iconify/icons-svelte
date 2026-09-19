<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5autgo_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="h5autgo_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:unsync-folder" {...props}></Icon>
