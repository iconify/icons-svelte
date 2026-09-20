<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxw_tdzlv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxw_tdzlv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:terror-fill" {...props}></Icon>
