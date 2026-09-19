<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-foc9irl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a-foc9irl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:suitcase-line" {...props}></Icon>
