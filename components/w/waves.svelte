<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq-_nebdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lq-_nebdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:waves" {...props}></Icon>
