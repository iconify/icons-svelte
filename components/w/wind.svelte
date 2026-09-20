<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq2tretia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oq2tretia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:wind" {...props}></Icon>
