<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gemmb2bwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gemmb2bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:table-2" {...props}></Icon>
