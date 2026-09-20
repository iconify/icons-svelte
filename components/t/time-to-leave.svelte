<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc7hk3brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc7hk3brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:time-to-leave" {...props}></Icon>
