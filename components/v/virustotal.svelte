<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9-evlb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9-evlb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:virustotal" {...props}></Icon>
