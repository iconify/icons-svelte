<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmujmvhfy.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9BO8tGmC"><path class="nmujmvhfy"/></mask></defs><path mask="url(#SVG9BO8tGmC)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:tool" {...props}></Icon>
