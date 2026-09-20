<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beckg56qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beckg56qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:transit-connection" {...props}></Icon>
