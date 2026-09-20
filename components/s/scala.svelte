<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxs9r3b1f.css';
import '../../css/r/rige9ccms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zxs9r3b1f"/><path class="rige9ccms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:scala" {...props}></Icon>
