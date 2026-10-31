<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijx--jbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijx--jbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:warning-duocolor-round" {...props}></Icon>
