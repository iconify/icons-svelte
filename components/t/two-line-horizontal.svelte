<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s66ne_bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s66ne_bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:two-line-horizontal" {...props}></Icon>
