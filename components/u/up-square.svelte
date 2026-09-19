<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/i/i7hww6ssd.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOaqYjePA"><g class="aql7dnt-u"><rect class="h9qj9o6mz"/><path class="i7hww6ssd"/></g></mask></defs><path mask="url(#SVGOaqYjePA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:up-square" {...props}></Icon>
