<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/r/rzkc8ryte.css';
import '../../css/y/y785qmzpn.css';
import '../../css/f/fif1ehbkk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlwsRHVWn"><g class="v3_i3wktz"><path clip-rule="evenodd" class="rzkc8ryte"/><path class="y785qmzpn"/><path class="fif1ehbkk"/></g></mask></defs><path mask="url(#SVGlwsRHVWn)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:ship" {...props}></Icon>
