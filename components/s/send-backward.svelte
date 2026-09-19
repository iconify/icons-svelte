<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/y/ynqx2zfnc.css';
import '../../css/o/odhm74bfl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGd09YJeLr"><g class="v3_i3wktz"><path class="ynqx2zfnc"/><path class="odhm74bfl"/></g></mask></defs><path mask="url(#SVGd09YJeLr)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:send-backward" {...props}></Icon>
