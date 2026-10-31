<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxlhkovva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nxlhkovva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:table-cells-split-solid" {...props}></Icon>
