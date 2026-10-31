<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qua3fz37b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qua3fz37b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tablet-button-round" {...props}></Icon>
