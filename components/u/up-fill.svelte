<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld6a4jbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld6a4jbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:up-fill" {...props}></Icon>
