<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl-9f5bep.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAMeIHcAT"><path class="sl-9f5bep"/></mask></defs><path mask="url(#SVGAMeIHcAT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:share-two" {...props}></Icon>
