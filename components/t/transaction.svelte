<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/u/ubq5zrksv.css';
import '../../css/f/fg6trmbac.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGuiyM6d6v"><g class="aql7dnt-u"><path class="ubq5zrksv"/><path class="fg6trmbac"/></g></mask></defs><path mask="url(#SVGuiyM6d6v)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:transaction" {...props}></Icon>
