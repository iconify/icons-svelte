<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wirxgc2mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wirxgc2mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:zoomin" {...props}></Icon>
