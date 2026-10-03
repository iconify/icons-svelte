<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw1-8ybcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw1-8ybcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:text-align-justify-start" {...props}></Icon>
