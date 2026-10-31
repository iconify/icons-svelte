<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xotu9nmgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xotu9nmgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:scan-text-gloss" {...props}></Icon>
