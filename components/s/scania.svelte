<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ike6rfddh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ike6rfddh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:scania" {...props}></Icon>
