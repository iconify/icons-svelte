<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xkieo5brz.css';
import '../../css/v/vi8de4bfs.css';
import '../../css/l/l8scj5ofw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnOHGUbKR"><g class="ft5dv1b6b"><path class="xkieo5brz"/><path class="vi8de4bfs"/><path class="l8scj5ofw"/></g></mask></defs><path mask="url(#SVGnOHGUbKR)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:skate" {...props}></Icon>
