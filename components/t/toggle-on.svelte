<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqalj6buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1280};
const content = `<path class="qqalj6buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:toggle-on" {...props}></Icon>
