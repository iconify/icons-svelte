<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d28uxbqja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d28uxbqja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sandglass-fill" {...props}></Icon>
