<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd96anb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd96anb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:skateboarding-fill" {...props}></Icon>
