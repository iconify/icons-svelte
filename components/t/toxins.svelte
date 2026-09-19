<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/h-3fmj80g.css';
import '../../css/p/pf56890je.css';
import '../../css/o/old3i1bqh.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMtj3lcpQ"><g class="v3_i3wktz"><path clip-rule="evenodd" class="h-3fmj80g"/><path class="pf56890je"/><path class="old3i1bqh"/></g></mask></defs><path mask="url(#SVGMtj3lcpQ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:toxins" {...props}></Icon>
