<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fig7rt_5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fig7rt_5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:shirt-1" {...props}></Icon>
