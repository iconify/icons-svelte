<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgyf-zbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgyf-zbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:slate-open-minus-outline" {...props}></Icon>
