<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfeutzb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfeutzb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-edit-filled" {...props}></Icon>
