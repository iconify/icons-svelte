<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3wwktf5z.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHIMz2cTY"><path class="a3wwktf5z"/></mask></defs><path mask="url(#SVGHIMz2cTY)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:two-two" {...props}></Icon>
