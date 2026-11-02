<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiha8cybs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tiha8cybs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:silent-line" {...props}></Icon>
