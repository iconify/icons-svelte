<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdc4_i2ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdc4_i2ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:traffic-light" {...props}></Icon>
