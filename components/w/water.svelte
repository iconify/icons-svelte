<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4wngcb6p.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhOoFSdeL"><path class="e4wngcb6p"/></mask></defs><path mask="url(#SVGhOoFSdeL)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:water" {...props}></Icon>
