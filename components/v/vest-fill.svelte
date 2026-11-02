<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usgq78dhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usgq78dhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vest-fill" {...props}></Icon>
