<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewjivobsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewjivobsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-number-7-filled" {...props}></Icon>
