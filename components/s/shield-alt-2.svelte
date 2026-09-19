<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2zodh4mf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2zodh4mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shield-alt-2" {...props}></Icon>
