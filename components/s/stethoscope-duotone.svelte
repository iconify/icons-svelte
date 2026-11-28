<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnztb7v3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vnztb7v3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:stethoscope-duotone" {...props}></Icon>
