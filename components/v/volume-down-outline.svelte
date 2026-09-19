<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlrf9sb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlrf9sb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:volume-down-outline" {...props}></Icon>
