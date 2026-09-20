<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0949d68q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0949d68q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:set-square" {...props}></Icon>
