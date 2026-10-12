<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq7mqvbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq7mqvbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:thermometer-sun-filled" {...props}></Icon>
