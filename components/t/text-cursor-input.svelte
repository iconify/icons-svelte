<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy05ngn_w.css';
import '../../css/r/r76_vnpan.css';
import '../../css/b/b3q0u7byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy05ngn_w wm-k"/><path class="r76_vnpan wm-a"/><path class="b3q0u7byj wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:text-cursor-input" {...props}></Icon>
