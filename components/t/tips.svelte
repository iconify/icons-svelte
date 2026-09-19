<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/o/ou761j2fu.css';
import '../../css/h/hk74r7aft.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwKWWnpan"><g class="aql7dnt-u"><path class="ou761j2fu"/><path class="hk74r7aft"/></g></mask></defs><path mask="url(#SVGwKWWnpan)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:tips" {...props}></Icon>
