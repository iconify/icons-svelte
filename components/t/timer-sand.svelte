<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n176kdbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n176kdbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-sand" {...props}></Icon>
