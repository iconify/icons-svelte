<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw93vibwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw93vibwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:screw-machine-flat-top" {...props}></Icon>
