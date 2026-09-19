<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2yu2lbpb.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOyPzUdDP"><path class="a2yu2lbpb"/></mask></defs><path mask="url(#SVGOyPzUdDP)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:sorcerer-hat" {...props}></Icon>
