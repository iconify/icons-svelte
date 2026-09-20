<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krh13ab-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krh13ab-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-remove" {...props}></Icon>
