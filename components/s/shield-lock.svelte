<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8-858bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8-858bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:shield-lock" {...props}></Icon>
