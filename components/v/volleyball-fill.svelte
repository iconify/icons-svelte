<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxtz1bcbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxtz1bcbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:volleyball-fill" {...props}></Icon>
