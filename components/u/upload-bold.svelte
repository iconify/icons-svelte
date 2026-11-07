<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2--zlbhj.css';
import '../../css/j/jqzwqyd4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2--zlbhj"/><path class="jqzwqyd4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:upload-bold" {...props}></Icon>
