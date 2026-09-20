<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-ustlblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-ustlblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sim-card-fill" {...props}></Icon>
