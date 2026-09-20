<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5h_q1b3w.css';
import '../../css/s/sltqfkbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5h_q1b3w"/><path class="sltqfkbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:yam" {...props}></Icon>
