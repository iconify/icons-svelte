<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zad-rl9dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zad-rl9dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:trend-micro" {...props}></Icon>
