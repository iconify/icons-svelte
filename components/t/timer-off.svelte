<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfpt253yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfpt253yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:timer-off" {...props}></Icon>
