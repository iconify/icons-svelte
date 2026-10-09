<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa37jgblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xa37jgblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:swimming-20" {...props}></Icon>
