<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcgcfnc6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcgcfnc6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:shopping-bag-arrow-down" {...props}></Icon>
