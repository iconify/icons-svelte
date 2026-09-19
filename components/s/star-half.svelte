<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_h2tywfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t_h2tywfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:star-half" {...props}></Icon>
