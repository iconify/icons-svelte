<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezox_nb2h.css';
import '../../css/s/sigw4fbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezox_nb2h"/><path class="sigw4fbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:slideshare" {...props}></Icon>
