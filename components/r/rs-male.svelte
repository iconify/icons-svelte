<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/b/bj2gztbde.css';
import '../../css/k/ka-b-fb0g.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGr9lWrdrs"><g class="aql7dnt-u"><path class="bj2gztbde"/><path class="ka-b-fb0g"/></g></mask></defs><path mask="url(#SVGr9lWrdrs)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:rs-male" {...props}></Icon>
