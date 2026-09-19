<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/b/bo0gd_fua.css';
import '../../css/i/itwm8w2av.css';
import '../../css/l/l99dlhbri.css';
import '../../css/w/wmsnpobfq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKDASGbCp"><g class="aql7dnt-u"><path class="bo0gd_fua"/><path class="itwm8w2av"/><path class="l99dlhbri"/><path class="wmsnpobfq"/></g></mask></defs><path mask="url(#SVGKDASGbCp)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:wheelchair" {...props}></Icon>
