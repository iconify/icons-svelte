<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h02w-12-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h02w-12-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sun2-filled" {...props}></Icon>
