<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/s/sl82esoas.css';
import '../../css/i/i5hbabbqv.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMjaQ4bhO"><g class="v3_i3wktz"><path class="sl82esoas"/><path class="i5hbabbqv"/></g></mask></defs><path mask="url(#SVGMjaQ4bhO)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:volume-up" {...props}></Icon>
