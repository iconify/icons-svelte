<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaw3enbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaw3enbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:t" {...props}></Icon>
