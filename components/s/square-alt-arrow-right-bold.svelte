<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd6bosi-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nd6bosi-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-alt-arrow-right-bold" {...props}></Icon>
