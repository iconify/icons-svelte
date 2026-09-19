<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/h/h9hcsnbsy.css';
import '../../css/k/kls3_nbwn.css';
import '../../css/u/ut31g4brz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnrGa7bhS"><g class="aql7dnt-u"><path class="h9hcsnbsy"/><path class="kls3_nbwn"/><path class="ut31g4brz"/></g></mask></defs><path mask="url(#SVGnrGa7bhS)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:tent-banner" {...props}></Icon>
