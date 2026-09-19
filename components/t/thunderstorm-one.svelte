<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/s/skf0-0h2g.css';
import '../../css/f/fruahub8w.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGbpYWDeOp"><g class="v3_i3wktz"><path class="skf0-0h2g"/><path class="fruahub8w"/></g></mask></defs><path mask="url(#SVGbpYWDeOp)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:thunderstorm-one" {...props}></Icon>
