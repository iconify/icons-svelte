<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0h6iq6ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0h6iq6ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:volume-slash-solid" {...props}></Icon>
