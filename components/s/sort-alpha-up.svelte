<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi11bxbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qi11bxbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:sort-alpha-up" {...props}></Icon>
