<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quiri2l_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quiri2l_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-settings-outline" {...props}></Icon>
