<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/a/aqh7ddbsu.css';
import '../../css/n/n3tpeh1mo.css';
import '../../css/m/mdec_jslv.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkYsT2cKT"><g class="s9cl3zbei"><circle class="aqh7ddbsu"/><rect transform="rotate(90 36.006 19.334)" class="n3tpeh1mo"/><rect transform="rotate(-180 36.006 29.852)" class="mdec_jslv"/></g></mask></defs><path mask="url(#SVGkYsT2cKT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:switch-one" {...props}></Icon>
