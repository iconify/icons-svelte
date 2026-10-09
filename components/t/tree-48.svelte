<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3_p_x84g.css';
import '../../css/v/ve426zb6c.css';
import '../../css/l/lx7eh7b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r3_p_x84g"/><path class="ve426zb6c"/><path class="lx7eh7b9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tree-48" {...props}></Icon>
