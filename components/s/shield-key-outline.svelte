<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmjg9xeev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmjg9xeev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-key-outline" {...props}></Icon>
