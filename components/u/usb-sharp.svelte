<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf56cje1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf56cje1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:usb-sharp" {...props}></Icon>
