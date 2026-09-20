<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4jpw2bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4jpw2bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:xls-fill" {...props}></Icon>
