<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic6slib8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic6slib8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tablet-solid" {...props}></Icon>
