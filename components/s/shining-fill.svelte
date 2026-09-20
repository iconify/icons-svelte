<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfxlm-_7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfxlm-_7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shining-fill" {...props}></Icon>
