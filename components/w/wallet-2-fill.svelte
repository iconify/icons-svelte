<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmbjghd0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmbjghd0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wallet-2-fill" {...props}></Icon>
