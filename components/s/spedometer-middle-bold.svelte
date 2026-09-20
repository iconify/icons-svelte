<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq84j_byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hq84j_byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:spedometer-middle-bold" {...props}></Icon>
