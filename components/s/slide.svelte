<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/p/pu6_gdjrb.css';
import '../../css/o/o-om9db6c.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4IeoacRd"><g class="v3_i3wktz"><path class="pu6_gdjrb"/><path class="o-om9db6c"/></g></mask></defs><path mask="url(#SVG4IeoacRd)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:slide" {...props}></Icon>
