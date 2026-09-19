<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd6ai1bvf.css';
import '../../css/y/yfgyogn5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="jd6ai1bvf"/><path clip-rule="evenodd" class="yfgyogn5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:unlock-filled" {...props}></Icon>
