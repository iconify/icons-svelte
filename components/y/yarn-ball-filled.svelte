<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8-h7-bhg.css';
import '../../css/h/h-_epdppu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8-h7-bhg"/><path class="h-_epdppu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:yarn-ball-filled" {...props}></Icon>
