<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpx8qtbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpx8qtbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:user-multiple-male-female" {...props}></Icon>
