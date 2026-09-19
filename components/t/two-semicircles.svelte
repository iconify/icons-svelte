<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_tzaabbz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCIj2QcHI"><path clip-rule="evenodd" class="h_tzaabbz"/></mask></defs><path mask="url(#SVGCIj2QcHI)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:two-semicircles" {...props}></Icon>
