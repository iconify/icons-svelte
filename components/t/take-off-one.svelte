<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/r/rs1g-shrt.css';
import '../../css/n/nm4514u-e.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGodHBteUQ"><g class="aql7dnt-u"><path class="rs1g-shrt"/><path class="nm4514u-e"/></g></mask></defs><path mask="url(#SVGodHBteUQ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:take-off-one" {...props}></Icon>
