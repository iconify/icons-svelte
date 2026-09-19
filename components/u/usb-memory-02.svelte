<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e31ph7fnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e31ph7fnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:usb-memory-02" {...props}></Icon>
