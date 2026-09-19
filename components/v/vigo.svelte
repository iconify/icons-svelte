<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo1tk3-8o.css';
import '../../css/x/x18puqb7i.css';
import '../../css/w/w8jozfhvk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAlPGBhXj"><g class="zo1tk3-8o"><path class="x18puqb7i"/><path class="w8jozfhvk"/></g></mask></defs><path mask="url(#SVGAlPGBhXj)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:vigo" {...props}></Icon>
