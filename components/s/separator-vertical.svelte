<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyj5a3q_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyj5a3q_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:separator-vertical" {...props}></Icon>
