<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhp46wbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhp46wbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video3-filled" {...props}></Icon>
