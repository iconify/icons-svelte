<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn9atv0gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn9atv0gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:scarf" {...props}></Icon>
