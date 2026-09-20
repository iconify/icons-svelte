<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p05zzxb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p05zzxb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:umbrella-beach-outline" {...props}></Icon>
