<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba8wc7b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba8wc7b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-alert" {...props}></Icon>
