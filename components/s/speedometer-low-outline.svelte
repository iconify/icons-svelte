<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrb4imbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nrb4imbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:speedometer-low-outline" {...props}></Icon>
