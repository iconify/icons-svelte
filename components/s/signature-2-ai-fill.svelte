<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7_ppxb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7_ppxb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:signature-2-ai-fill" {...props}></Icon>
