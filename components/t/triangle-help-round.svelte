<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjk_vvbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjk_vvbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:triangle-help-round" {...props}></Icon>
