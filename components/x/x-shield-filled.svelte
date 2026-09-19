<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc9gedb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc9gedb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:x-shield-filled" {...props}></Icon>
