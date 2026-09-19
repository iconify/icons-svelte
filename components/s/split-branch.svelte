<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v_j2mjbpq.css';
import '../../css/i/iiqksgb7d.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGphGeOdXM"><g class="ft5dv1b6b"><path class="v_j2mjbpq"/><path class="iiqksgb7d"/></g></mask></defs><path mask="url(#SVGphGeOdXM)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:split-branch" {...props}></Icon>
