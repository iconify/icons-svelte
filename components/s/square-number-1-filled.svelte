<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkup8_7we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkup8_7we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-number-1-filled" {...props}></Icon>
