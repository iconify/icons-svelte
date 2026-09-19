<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u470c7btl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIsYipbDd"><path class="u470c7btl"/></mask></defs><path mask="url(#SVGIsYipbDd)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:three" {...props}></Icon>
