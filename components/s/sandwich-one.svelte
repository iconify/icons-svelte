<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/h/h9ei6dbpa.css';
import '../../css/u/u7k-t2blh.css';
import '../../css/f/f-g4jnfew.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBQsS7c4f"><g class="aql7dnt-u"><path class="h9ei6dbpa"/><rect transform="rotate(-45 5.071 33.071)" class="u7k-t2blh"/><path class="f-g4jnfew"/></g></mask></defs><path mask="url(#SVGBQsS7c4f)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:sandwich-one" {...props}></Icon>
