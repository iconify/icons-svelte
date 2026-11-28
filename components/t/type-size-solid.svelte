<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue6f4x97e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue6f4x97e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:type-size-solid" {...props}></Icon>
