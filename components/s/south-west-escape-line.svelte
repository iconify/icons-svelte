<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnu0hceal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnu0hceal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:south-west-escape-line" {...props}></Icon>
