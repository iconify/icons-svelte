<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fh8rzobwg.css';
import '../../css/m/m7zug4ylz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJb7QgivB"><g class="v3_i3wktz"><path class="fh8rzobwg"/><path class="m7zug4ylz"/></g></mask></defs><path mask="url(#SVGJb7QgivB)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:zoom-in" {...props}></Icon>
