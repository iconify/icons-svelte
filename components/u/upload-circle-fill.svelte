<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsu6aob7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="wsu6aob7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:upload-circle-fill" {...props}></Icon>
