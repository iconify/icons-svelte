<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr9-5dbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qr9-5dbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:trash-one-solid" {...props}></Icon>
