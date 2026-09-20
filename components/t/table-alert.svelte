<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih1ytcvyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih1ytcvyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-alert" {...props}></Icon>
