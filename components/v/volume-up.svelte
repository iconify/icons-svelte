<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4cqtxb4q.css';
import '../../css/r/rrw1wrbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4cqtxb4q"/><path class="rrw1wrbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:volume-up" {...props}></Icon>
