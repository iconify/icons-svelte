<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxcflrbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxcflrbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stop-circle-fill" {...props}></Icon>
