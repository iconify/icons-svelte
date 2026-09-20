<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1ex4ob1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h1ex4ob1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rss" {...props}></Icon>
