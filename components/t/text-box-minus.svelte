<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhd83ub7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhd83ub7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:text-box-minus" {...props}></Icon>
