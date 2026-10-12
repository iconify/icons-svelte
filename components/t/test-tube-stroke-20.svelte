<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6y1d0ihj.css';
import '../../css/y/ykou9hbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x6y1d0ihj"/><path class="ykou9hbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:test-tube-stroke-20" {...props}></Icon>
