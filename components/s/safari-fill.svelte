<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-fiq5b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-fiq5b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safari-fill" {...props}></Icon>
