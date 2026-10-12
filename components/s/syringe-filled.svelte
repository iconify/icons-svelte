<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4mad_nxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k4mad_nxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:syringe-filled" {...props}></Icon>
