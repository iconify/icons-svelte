<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsaw33-sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zsaw33-sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:unsync-occurence" {...props}></Icon>
