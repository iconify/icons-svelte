<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k27a35brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1600,"height":1536};
const content = `<path class="k27a35brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:thumbs-up" {...props}></Icon>
