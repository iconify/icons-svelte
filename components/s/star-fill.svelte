<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-1nsqbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-1nsqbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:star-fill" {...props}></Icon>
