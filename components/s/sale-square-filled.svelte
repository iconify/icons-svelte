<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7mxl3b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e7mxl3b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sale-square-filled" {...props}></Icon>
