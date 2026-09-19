<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qikil81ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qikil81ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:shortcode" {...props}></Icon>
