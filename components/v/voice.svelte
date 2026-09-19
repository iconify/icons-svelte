<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/k9anlbbxt.css';
import '../../css/h/h2x2yzbat.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGI0ofmUkm"><g class="v3_i3wktz"><rect class="k9anlbbxt"/><path class="h2x2yzbat"/></g></mask></defs><path mask="url(#SVGI0ofmUkm)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:voice" {...props}></Icon>
