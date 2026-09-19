<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9ge0xych.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b d9ge0xych"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:size-uniform" {...props}></Icon>
