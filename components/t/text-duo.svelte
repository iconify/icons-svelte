<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liqwdbc2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="liqwdbc2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:text-duo" {...props}></Icon>
