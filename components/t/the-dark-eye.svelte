<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnvjofq_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnvjofq_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:the-dark-eye" {...props}></Icon>
