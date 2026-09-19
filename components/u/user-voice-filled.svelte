<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmp9nzblx.css';
import '../../css/f/fnb-t_u4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmp9nzblx"/><path class="fnb-t_u4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-voice-filled" {...props}></Icon>
