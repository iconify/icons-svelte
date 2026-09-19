<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki7z1mb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ki7z1mb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:shield" {...props}></Icon>
