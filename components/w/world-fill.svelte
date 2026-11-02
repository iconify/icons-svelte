<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaqikjatt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eaqikjatt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:world-fill" {...props}></Icon>
