<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/g/ge5cflqyw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKePsed6S"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="ge5cflqyw"/></g></mask></defs><path mask="url(#SVGKePsed6S)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:slightly-frowning-face-whit-open-mouth" {...props}></Icon>
