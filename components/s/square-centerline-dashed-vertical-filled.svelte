<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8qrl_cai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8qrl_cai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-centerline-dashed-vertical-filled" {...props}></Icon>
