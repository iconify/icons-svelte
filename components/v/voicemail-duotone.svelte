<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dogucbccx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dogucbccx primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:voicemail-duotone" {...props}></Icon>
