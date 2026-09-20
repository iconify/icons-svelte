<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f54y-9dgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f54y-9dgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-c-filled" {...props}></Icon>
