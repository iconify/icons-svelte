<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsoc7jbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsoc7jbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-4" {...props}></Icon>
