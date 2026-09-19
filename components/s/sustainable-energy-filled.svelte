<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vie_2cbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vie_2cbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sustainable-energy-filled" {...props}></Icon>
