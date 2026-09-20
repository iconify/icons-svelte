<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4uowd9uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4uowd9uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wallet-4-fill" {...props}></Icon>
