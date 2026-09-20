<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhk-4s-mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhk-4s-mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:yen" {...props}></Icon>
