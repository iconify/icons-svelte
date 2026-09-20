<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sma0iqctz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sma0iqctz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:stop-square-fill" {...props}></Icon>
