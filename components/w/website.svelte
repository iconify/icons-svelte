<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja0jd1bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="ja0jd1bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:website" {...props}></Icon>
