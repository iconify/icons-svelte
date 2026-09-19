<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw617_bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qw617_bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:usb-off" {...props}></Icon>
