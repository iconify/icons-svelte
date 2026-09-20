<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owpd0cb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owpd0cb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tongue-fill" {...props}></Icon>
