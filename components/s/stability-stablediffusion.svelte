<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai6km_1tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai6km_1tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stability-stablediffusion" {...props}></Icon>
