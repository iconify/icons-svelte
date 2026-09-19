<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lml0hibhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lml0hibhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-up-02" {...props}></Icon>
