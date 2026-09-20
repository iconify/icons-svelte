<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7_2ksbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7_2ksbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shopping-basket-2-fill" {...props}></Icon>
