<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb7sowwzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-4};
const content = `<path class="tb7sowwzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:stop" {...props}></Icon>
