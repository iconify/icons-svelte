<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_u8q-bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_u8q-bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:settings-6-fill" {...props}></Icon>
