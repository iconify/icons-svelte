<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh-h126fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uh-h126fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wind-filled" {...props}></Icon>
