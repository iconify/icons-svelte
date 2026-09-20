<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfrikpbvv.css';
import '../../css/e/etxysdbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfrikpbvv"/><path class="etxysdbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:trash-alt" {...props}></Icon>
