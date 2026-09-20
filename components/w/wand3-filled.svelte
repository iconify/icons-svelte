<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4v_j9b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4v_j9b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wand3-filled" {...props}></Icon>
