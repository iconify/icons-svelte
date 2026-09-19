<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm_8_wbdg.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQJe1xbJd"><path class="jm_8_wbdg"/></mask></defs><path mask="url(#SVGQJe1xbJd)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:windows" {...props}></Icon>
