<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkuojebws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkuojebws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:shield-alert" {...props}></Icon>
