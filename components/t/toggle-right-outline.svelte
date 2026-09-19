<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nakc4kdbz.css';
import '../../css/q/qn6af91zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nakc4kdbz"/><path class="qn6af91zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:toggle-right-outline" {...props}></Icon>
