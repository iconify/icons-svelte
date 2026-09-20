<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utftrq6kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utftrq6kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-asterisk-filled" {...props}></Icon>
