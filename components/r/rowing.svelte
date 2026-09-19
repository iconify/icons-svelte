<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgga7abld.css';
import '../../css/y/yplbaw3db.css';
import '../../css/j/jkcu7kbhq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGiGiSwbSe"><g class="cgga7abld"><path class="yplbaw3db"/><path class="jkcu7kbhq"/></g></mask></defs><path mask="url(#SVGiGiSwbSe)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:rowing" {...props}></Icon>
