<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6f890vvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6f890vvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wallet-fill" {...props}></Icon>
