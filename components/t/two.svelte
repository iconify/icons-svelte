<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crrxqfb0f.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnTiqDe6y"><path class="crrxqfb0f"/></mask></defs><path mask="url(#SVGnTiqDe6y)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:two" {...props}></Icon>
