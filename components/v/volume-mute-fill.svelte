<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk0zo2kay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk0zo2kay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:volume-mute-fill" {...props}></Icon>
