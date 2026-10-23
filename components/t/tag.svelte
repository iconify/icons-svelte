<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh2rnzj_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh2rnzj_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tag" {...props}></Icon>
