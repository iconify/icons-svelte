<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoc91eerl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGr4OnveXX"><path class="aoc91eerl"/></mask></defs><path mask="url(#SVGr4OnveXX)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:waterfalls-h" {...props}></Icon>
