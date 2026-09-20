<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfy5v1ddq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfy5v1ddq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ztg" {...props}></Icon>
