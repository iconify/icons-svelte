<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjhnb3boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjhnb3boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:user-multiple-minus" {...props}></Icon>
