<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcif0d1_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcif0d1_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:scooter-3-bold" {...props}></Icon>
