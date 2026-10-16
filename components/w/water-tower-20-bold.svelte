<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvj-7zctj.css';
import '../../css/q/qn7t179un.css';
import '../../css/k/k-26e659n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hvj-7zctj"/><path class="qn7t179un"/><path class="k-26e659n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-tower-20-bold" {...props}></Icon>
