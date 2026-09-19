<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/r/r5tlskk2v.css';
import '../../css/e/el5co48gm.css';
import '../../css/q/qk9ee1x_u.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRMaSpcHZ"><g class="ufeehvblu"><path class="r5tlskk2v"/><path class="el5co48gm"/><path class="qk9ee1x_u"/></g></mask></defs><path mask="url(#SVGRMaSpcHZ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:stopwatch" {...props}></Icon>
