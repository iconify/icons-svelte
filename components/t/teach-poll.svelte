<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2mha9b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2mha9b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:teach-poll" {...props}></Icon>
