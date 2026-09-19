<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1yuyjz7c.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8oel7IvX"><path class="z1yuyjz7c"/></mask></defs><path mask="url(#SVG8oel7IvX)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:vertical-tidy-up" {...props}></Icon>
