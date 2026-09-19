<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fngjr_1gm.css';
import '../../css/w/wsc1fl-xl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWWivydVe"><g class="v3_i3wktz"><path class="fngjr_1gm"/><path clip-rule="evenodd" class="wsc1fl-xl"/></g></mask></defs><path mask="url(#SVGWWivydVe)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:swallow" {...props}></Icon>
