<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_4s_obaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_4s_obaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:spam" {...props}></Icon>
