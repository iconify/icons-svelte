<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwx2k6b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwx2k6b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:smile-squint-wink-alt" {...props}></Icon>
