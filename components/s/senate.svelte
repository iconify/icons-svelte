<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it17_8b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it17_8b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:senate" {...props}></Icon>
