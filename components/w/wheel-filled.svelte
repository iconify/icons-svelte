<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5pwt9byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h5pwt9byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wheel-filled" {...props}></Icon>
