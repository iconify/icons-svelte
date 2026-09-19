<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/r/rtwj0brya.css';
import '../../css/u/umq8qcomr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMCtwEc4r"><g class="aql7dnt-u"><path class="rtwj0brya"/><path class="umq8qcomr"/></g></mask></defs><path mask="url(#SVGMCtwEc4r)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:six-circular-connection" {...props}></Icon>
