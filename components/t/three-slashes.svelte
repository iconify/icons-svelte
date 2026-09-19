<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcy96uaty.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvq0smcdQ"><path class="fcy96uaty"/></mask></defs><path mask="url(#SVGvq0smcdQ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:three-slashes" {...props}></Icon>
