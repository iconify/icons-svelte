<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em8stgbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em8stgbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:wind-energy-alt-filled" {...props}></Icon>
