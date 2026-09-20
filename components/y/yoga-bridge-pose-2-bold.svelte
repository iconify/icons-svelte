<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmk_r7b-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pmk_r7b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:yoga-bridge-pose-2-bold" {...props}></Icon>
