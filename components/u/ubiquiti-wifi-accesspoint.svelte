<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynkwuebdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynkwuebdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ubiquiti-wifi-accesspoint" {...props}></Icon>
