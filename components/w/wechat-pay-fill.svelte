<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clivd6btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clivd6btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:wechat-pay-fill" {...props}></Icon>
