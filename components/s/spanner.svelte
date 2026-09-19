<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffn7vc-5q.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZOMjqdzR"><path class="ffn7vc-5q"/></mask></defs><path mask="url(#SVGZOMjqdzR)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:spanner" {...props}></Icon>
