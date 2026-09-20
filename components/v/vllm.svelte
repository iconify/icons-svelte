<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dixa9hblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dixa9hblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:vllm" {...props}></Icon>
