<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh44o54vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lh44o54vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:serverless" {...props}></Icon>
