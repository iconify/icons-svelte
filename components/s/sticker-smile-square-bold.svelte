<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcmgtpbjl.css';
import '../../css/y/ysujvx2kd.css';
import '../../css/n/npbc0r39g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hcmgtpbjl"/><path class="ysujvx2kd"/><path clip-rule="evenodd" class="npbc0r39g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sticker-smile-square-bold" {...props}></Icon>
