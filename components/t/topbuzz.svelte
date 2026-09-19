<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a67hi8bws.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGg3e8VdEc"><path class="a67hi8bws"/></mask></defs><path mask="url(#SVGg3e8VdEc)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:topbuzz" {...props}></Icon>
