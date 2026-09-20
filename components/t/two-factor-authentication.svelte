<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i09v-mbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i09v-mbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:two-factor-authentication" {...props}></Icon>
