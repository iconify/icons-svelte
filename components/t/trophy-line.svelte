<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwcfi3o_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwcfi3o_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:trophy-line" {...props}></Icon>
