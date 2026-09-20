<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxj2tvb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxj2tvb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:sliders-v-light" {...props}></Icon>
