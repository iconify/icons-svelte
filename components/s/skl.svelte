<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5921bc9b.css';
import '../../css/u/uijq5ybza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5921bc9b"/><path class="uijq5ybza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:skl" {...props}></Icon>
