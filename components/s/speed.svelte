<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/m/mm0oaabax.css';
import '../../css/u/u_r6ezb6m.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGeomlRcTD"><g class="v3_i3wktz"><path class="mm0oaabax"/><path class="u_r6ezb6m"/></g></mask></defs><path mask="url(#SVGeomlRcTD)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:speed" {...props}></Icon>
