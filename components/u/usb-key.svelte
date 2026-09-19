<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q07hkebjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q07hkebjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:usb-key" {...props}></Icon>
