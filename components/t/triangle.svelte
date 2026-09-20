<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-4dk0bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-4dk0bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:triangle" {...props}></Icon>
