<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwqp85_nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kwqp85_nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:trash" {...props}></Icon>
