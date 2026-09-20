<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjv2x3bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjv2x3bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shield2-filled" {...props}></Icon>
