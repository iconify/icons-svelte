<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0v79xv_p.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOLMCCemi"><path class="y0v79xv_p"/></mask></defs><path mask="url(#SVGOLMCCemi)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:yep" {...props}></Icon>
