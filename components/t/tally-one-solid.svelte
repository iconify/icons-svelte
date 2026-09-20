<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmekq-6-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmekq-6-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tally-one-solid" {...props}></Icon>
