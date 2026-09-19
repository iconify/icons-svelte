<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxfo8c2li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="gxfo8c2li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:share-outline" {...props}></Icon>
