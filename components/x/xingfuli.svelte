<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m2blynbna.css';
import '../../css/d/dyg28cb_c.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEbUP3Hyh"><g class="s9cl3zbei"><path class="m2blynbna"/><path class="dyg28cb_c"/></g></mask></defs><path mask="url(#SVGEbUP3Hyh)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:xingfuli" {...props}></Icon>
