<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qglutibcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qglutibcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:sunny" {...props}></Icon>
