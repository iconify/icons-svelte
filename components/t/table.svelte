<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/d/dzhl58nwn.css';
import '../../css/w/wk8bg5zve.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLQsOGbhf"><g class="aql7dnt-u"><rect class="dzhl58nwn"/><path class="wk8bg5zve"/></g></mask></defs><path mask="url(#SVGLQsOGbhf)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:table" {...props}></Icon>
