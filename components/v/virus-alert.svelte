<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-b3neb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-b3neb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:virus-alert" {...props}></Icon>
