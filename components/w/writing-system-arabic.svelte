<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiu31ywbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiu31ywbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:writing-system-arabic" {...props}></Icon>
