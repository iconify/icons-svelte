<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h67-4dtga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h67-4dtga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-sync" {...props}></Icon>
