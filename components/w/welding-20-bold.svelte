<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzs4rus3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nzs4rus3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:welding-20-bold" {...props}></Icon>
