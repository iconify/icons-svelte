<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psukv_bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="psukv_bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:smart-speaker3-filled" {...props}></Icon>
