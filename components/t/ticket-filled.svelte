<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj0bvrbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uj0bvrbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ticket-filled" {...props}></Icon>
