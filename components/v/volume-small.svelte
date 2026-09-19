<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/s/sl82esoas.css';
import '../../css/c/cchyt3b-e.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGV6DRCc9a"><g class="v3_i3wktz"><path class="sl82esoas"/><path class="cchyt3b-e"/></g></mask></defs><path mask="url(#SVGV6DRCc9a)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:volume-small" {...props}></Icon>
