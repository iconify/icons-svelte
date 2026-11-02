<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f15xpgbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f15xpgbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:signature-2-fill" {...props}></Icon>
