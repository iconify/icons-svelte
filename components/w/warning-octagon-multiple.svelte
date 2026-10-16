<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-5s4sbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-5s4sbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:warning-octagon-multiple" {...props}></Icon>
