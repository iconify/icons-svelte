<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsk84s32m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsk84s32m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zap-round" {...props}></Icon>
