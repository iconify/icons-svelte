<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/x_-1fk5qn.css';
import '../../css/u/u1r09_bgv.css';
import '../../css/l/loc2q-8hs.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXAla8c4b"><g class="v3_i3wktz"><path class="x_-1fk5qn"/><path class="u1r09_bgv"/><path class="loc2q-8hs"/></g></mask></defs><path mask="url(#SVGXAla8c4b)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:sun" {...props}></Icon>
