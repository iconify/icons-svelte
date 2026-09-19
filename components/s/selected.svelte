<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/d9ti0tfzb.css';
import '../../css/w/wjxv5acdy.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnujFrm8B"><g class="v3_i3wktz"><path class="d9ti0tfzb"/><path class="wjxv5acdy"/></g></mask></defs><path mask="url(#SVGnujFrm8B)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:selected" {...props}></Icon>
