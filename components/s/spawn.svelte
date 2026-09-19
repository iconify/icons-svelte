<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlwy_6z1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dlwy_6z1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:spawn" {...props}></Icon>
