<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc1vmxbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc1vmxbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shield-cog-corner" {...props}></Icon>
