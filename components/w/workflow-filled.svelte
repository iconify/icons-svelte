<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnj986iyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnj986iyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:workflow-filled" {...props}></Icon>
