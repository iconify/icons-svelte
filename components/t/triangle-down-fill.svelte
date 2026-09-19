<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4h25zd1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4h25zd1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:triangle-down-fill" {...props}></Icon>
