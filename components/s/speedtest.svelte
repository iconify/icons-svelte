<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0m8e1b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0m8e1b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:speedtest" {...props}></Icon>
