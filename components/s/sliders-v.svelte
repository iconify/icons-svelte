<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g64y4bcfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g64y4bcfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sliders-v" {...props}></Icon>
