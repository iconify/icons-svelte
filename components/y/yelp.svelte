<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzzypybkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzzypybkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:yelp" {...props}></Icon>
