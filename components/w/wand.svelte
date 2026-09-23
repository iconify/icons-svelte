<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4eos-rnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4eos-rnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wand" {...props}></Icon>
