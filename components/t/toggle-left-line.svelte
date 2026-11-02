<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp-ka5bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp-ka5bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toggle-left-line" {...props}></Icon>
