<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdo0w_bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdo0w_bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:suitcase-2-fill" {...props}></Icon>
