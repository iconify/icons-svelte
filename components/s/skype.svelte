<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_y09c_tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s_y09c_tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:skype" {...props}></Icon>
