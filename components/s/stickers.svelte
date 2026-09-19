<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/l/lb6btw-nh.css';
import '../../css/m/mza0vib7z.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8OMmXcdh"><g class="aql7dnt-u"><path class="lb6btw-nh"/><path class="mza0vib7z"/></g></mask></defs><path mask="url(#SVG8OMmXcdh)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:stickers" {...props}></Icon>
