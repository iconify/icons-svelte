<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fxa5t9bup.css';
import '../../css/q/qcs51wjjn.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNmP5XcQo"><g class="v3_i3wktz"><path class="fxa5t9bup"/><path class="qcs51wjjn"/></g></mask></defs><path mask="url(#SVGNmP5XcQo)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:sofa" {...props}></Icon>
