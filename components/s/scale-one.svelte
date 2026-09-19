<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/dki2qy46y.css';
import '../../css/x/xjr1w6faa.css';
import '../../css/x/x1pn6ebie.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJQGaudKX"><g class="v3_i3wktz"><path class="dki2qy46y"/><path class="xjr1w6faa"/><path class="x1pn6ebie"/></g></mask></defs><path mask="url(#SVGJQGaudKX)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:scale-one" {...props}></Icon>
