<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-yl0srap.css';
import '../../css/f/fexna311s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-yl0srap"/><path class="fexna311s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:temperature-thermometer-up-bold" {...props}></Icon>
