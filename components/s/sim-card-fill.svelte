<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onpg9jxlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onpg9jxlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:sim-card-fill" {...props}></Icon>
