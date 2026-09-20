<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmlo9qblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmlo9qblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rounded-corner" {...props}></Icon>
