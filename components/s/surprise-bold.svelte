<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj2bnvbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="yj2bnvbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:surprise-bold" {...props}></Icon>
