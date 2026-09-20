<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8l6_iblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8l6_iblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vest-fill" {...props}></Icon>
