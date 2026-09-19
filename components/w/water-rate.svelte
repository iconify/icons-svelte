<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/amol9fbgq.css';
import '../../css/j/jk8ff9tlc.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWLQvjenu"><g class="v3_i3wktz"><path class="amol9fbgq"/><path class="jk8ff9tlc"/></g></mask></defs><path mask="url(#SVGWLQvjenu)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:water-rate" {...props}></Icon>
