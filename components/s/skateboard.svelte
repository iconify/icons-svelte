<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-_3mcbkz.css';
import '../../css/v/vikdu2bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-_3mcbkz"/><path class="vikdu2bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:skateboard" {...props}></Icon>
