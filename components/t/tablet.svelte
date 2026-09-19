<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-1idns3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-1idns3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tablet" {...props}></Icon>
