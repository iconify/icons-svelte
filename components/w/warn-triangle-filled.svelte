<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leqet9sky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="leqet9sky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:warn-triangle-filled" {...props}></Icon>
