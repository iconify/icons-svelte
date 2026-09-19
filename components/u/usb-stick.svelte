<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5mdhib7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o5mdhib7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:usb-stick" {...props}></Icon>
