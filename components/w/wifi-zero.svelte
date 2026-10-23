<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlvf8bc8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlvf8bc8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:wifi-zero" {...props}></Icon>
