<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmd6mmf_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmd6mmf_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:t-shirt-2-fill" {...props}></Icon>
