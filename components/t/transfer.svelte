<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldbtn_0ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldbtn_0ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:transfer" {...props}></Icon>
