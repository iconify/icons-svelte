<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmde6-b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmde6-b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:workflow-alt-filled" {...props}></Icon>
