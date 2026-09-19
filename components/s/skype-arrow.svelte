<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbn2c2bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bbn2c2bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:skype-arrow" {...props}></Icon>
