<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n61vkeq-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n61vkeq-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:upload-06" {...props}></Icon>
