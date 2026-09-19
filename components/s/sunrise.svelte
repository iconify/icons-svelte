<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocf1b88pq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ocf1b88pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sunrise" {...props}></Icon>
