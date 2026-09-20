<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu21_9btv.css';
import '../../css/y/ygivrbbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hu21_9btv"/><path class="ygivrbbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:screw-nut" {...props}></Icon>
