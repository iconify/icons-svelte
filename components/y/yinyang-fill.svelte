<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgry37bbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgry37bbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:yinyang-fill" {...props}></Icon>
