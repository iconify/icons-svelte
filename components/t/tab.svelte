<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp84et6rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp84et6rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:tab" {...props}></Icon>
