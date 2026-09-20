<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm8mg3bjf.css';
import '../../css/o/o4nmjxj6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm8mg3bjf"/><path class="o4nmjxj6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:veur" {...props}></Icon>
