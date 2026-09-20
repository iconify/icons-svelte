<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov8ljqhgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov8ljqhgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shopping-basket-minus-outline" {...props}></Icon>
