<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea5qyqbox.css';
import '../../css/d/dt2gkbchm.css';
import '../../css/v/vhwau7bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea5qyqbox wm-a"/><path class="dt2gkbchm wm-k"/><path class="vhwau7bwl wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:route" {...props}></Icon>
