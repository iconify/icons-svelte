<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/c/crnb93ntl.css';
import '../../css/c/c575j-byr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKkdZ2csA"><g class="wwvp95byt"><path class="crnb93ntl"/><path class="c575j-byr"/></g></mask></defs><path mask="url(#SVGKkdZ2csA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:success" {...props}></Icon>
