<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz6-h_4-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz6-h_4-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:wifi-slash" {...props}></Icon>
