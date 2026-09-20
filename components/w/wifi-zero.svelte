<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kneeq5ung.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kneeq5ung"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:wifi-zero" {...props}></Icon>
