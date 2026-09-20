<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twoxdzb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="twoxdzb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:volume-2" {...props}></Icon>
