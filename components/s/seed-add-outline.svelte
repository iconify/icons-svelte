<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiezucc0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yiezucc0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:seed-add-outline" {...props}></Icon>
