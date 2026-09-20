<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-flpfq5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-flpfq5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:star-circle-fill" {...props}></Icon>
