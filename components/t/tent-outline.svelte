<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dofh-nm5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dofh-nm5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tent-outline" {...props}></Icon>
