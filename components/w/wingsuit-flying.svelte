<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgga7abld.css';
import '../../css/s/si50jvboo.css';
import '../../css/b/bf_msp58c.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhNHrpdRn"><g class="cgga7abld"><path class="si50jvboo"/><path class="bf_msp58c"/></g></mask></defs><path mask="url(#SVGhNHrpdRn)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:wingsuit-flying" {...props}></Icon>
