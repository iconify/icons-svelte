<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj_99kb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wj_99kb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:scale-to-original" {...props}></Icon>
