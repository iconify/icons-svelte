<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz-s85hno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz-s85hno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-number-2-filled" {...props}></Icon>
