<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/fsx1iv68d.css';
import '../../css/a/as4b8ybnt.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGk42sHeYg"><g class="aql7dnt-u"><path class="fsx1iv68d"/><path class="as4b8ybnt"/></g></mask></defs><path mask="url(#SVGk42sHeYg)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:tomato" {...props}></Icon>
