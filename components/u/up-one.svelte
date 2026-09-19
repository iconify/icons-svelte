<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf493jmyr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOquiGdSs"><path class="cf493jmyr"/></mask></defs><path mask="url(#SVGOquiGdSs)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:up-one" {...props}></Icon>
