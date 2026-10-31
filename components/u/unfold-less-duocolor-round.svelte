<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpks6aclr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpks6aclr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:unfold-less-duocolor-round" {...props}></Icon>
