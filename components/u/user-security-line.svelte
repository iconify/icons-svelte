<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv94u5byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv94u5byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-security-line" {...props}></Icon>
