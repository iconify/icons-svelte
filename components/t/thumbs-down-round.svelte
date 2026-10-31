<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfu-blbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfu-blbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:thumbs-down-round" {...props}></Icon>
