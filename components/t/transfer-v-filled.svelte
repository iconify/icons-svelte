<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqusm6bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqusm6bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:transfer-v-filled" {...props}></Icon>
