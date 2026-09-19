<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw_qod65h.css';
import '../../css/h/hyjd_db4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="aw_qod65h"/><path class="hyjd_db4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:se-4x3" {...props}></Icon>
