<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocgeu8bid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ocgeu8bid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:water-glass" {...props}></Icon>
