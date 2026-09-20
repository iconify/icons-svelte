<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obnvicbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obnvicbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tumblr-reblog" {...props}></Icon>
