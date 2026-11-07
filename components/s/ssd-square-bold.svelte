<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj_moacsg.css';
import '../../css/s/s2bjr04lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj_moacsg"/><path clip-rule="evenodd" class="s2bjr04lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ssd-square-bold" {...props}></Icon>
