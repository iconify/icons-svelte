<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgga7abld.css';
import '../../css/l/lbjs96bea.css';
import '../../css/d/dm_j5gglv.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMjWPne7J"><g class="cgga7abld"><path class="lbjs96bea"/><path class="dm_j5gglv"/></g></mask></defs><path mask="url(#SVGMjWPne7J)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:weightlifting" {...props}></Icon>
