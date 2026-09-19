<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv8q85bdl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGsOJTOejQ"><path class="jv8q85bdl"/></mask></defs><path mask="url(#SVGsOJTOejQ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:thermometer-one" {...props}></Icon>
