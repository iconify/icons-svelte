<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta8351udl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ta8351udl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:times-duo" {...props}></Icon>
