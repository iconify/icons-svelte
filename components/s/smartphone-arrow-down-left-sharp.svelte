<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww42af3bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ww42af3bs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:smartphone-arrow-down-left-sharp" {...props}></Icon>
