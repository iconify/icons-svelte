<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le1y_9kop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le1y_9kop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:stars-c-fill" {...props}></Icon>
