<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6g-cwbpb.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQlSZBd9z"><path class="r6g-cwbpb"/></mask></defs><path mask="url(#SVGQlSZBd9z)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:trapezoid" {...props}></Icon>
