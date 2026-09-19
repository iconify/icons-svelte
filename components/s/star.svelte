<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj8gq3bcg.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTuN6OeRa"><path class="jj8gq3bcg"/></mask></defs><path mask="url(#SVGTuN6OeRa)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:star" {...props}></Icon>
