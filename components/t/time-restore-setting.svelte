<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln-j0jbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":384};
const content = `<path class="ln-j0jbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:time-restore-setting" {...props}></Icon>
