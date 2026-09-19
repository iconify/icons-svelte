<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1n80sbjy.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4tu5obwu"><path class="d1n80sbjy"/></mask></defs><path mask="url(#SVG4tu5obwu)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:waterfalls-v" {...props}></Icon>
