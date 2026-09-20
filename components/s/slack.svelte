<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dod7siuvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dod7siuvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:slack" {...props}></Icon>
