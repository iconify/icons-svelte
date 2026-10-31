<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thxt7mbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thxt7mbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:windows-logo-round" {...props}></Icon>
