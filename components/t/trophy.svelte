<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_q6zofxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7,"top":-2};
const content = `<path class="z_q6zofxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:trophy" {...props}></Icon>
