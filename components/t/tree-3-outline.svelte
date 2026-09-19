<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgfxdobrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="lgfxdobrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tree-3-outline" {...props}></Icon>
