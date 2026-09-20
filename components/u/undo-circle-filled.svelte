<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waor1ybrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="waor1ybrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:undo-circle-filled" {...props}></Icon>
