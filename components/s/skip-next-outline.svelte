<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc6rf6byt.css';
import '../../css/i/icodl6btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hc6rf6byt"/><path class="icodl6btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skip-next-outline" {...props}></Icon>
