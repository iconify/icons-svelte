<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0tc6jbsw.css';
import '../../css/f/f1o6q914t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0tc6jbsw wm-k"/><path class="f1o6q914t wm-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:zap-off" {...props}></Icon>
