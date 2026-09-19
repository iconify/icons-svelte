<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt9639byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tt9639byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:wink-bold" {...props}></Icon>
