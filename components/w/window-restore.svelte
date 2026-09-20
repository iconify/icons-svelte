<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgp7bubto.css';
import '../../css/k/kbad1107b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgp7bubto"/><path class="kbad1107b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:window-restore" {...props}></Icon>
