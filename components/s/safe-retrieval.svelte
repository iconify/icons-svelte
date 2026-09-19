<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/h/hcbdvv4aj.css';
import '../../css/p/pcjt9699v.css';
import '../../css/y/y79a7nr1h.css';
import '../../css/g/ghz63mbqk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKo8WneWO"><g class="ufeehvblu"><path class="hcbdvv4aj"/><path class="pcjt9699v"/><path class="y79a7nr1h"/><path class="ghz63mbqk"/></g></mask></defs><path mask="url(#SVGKo8WneWO)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:safe-retrieval" {...props}></Icon>
