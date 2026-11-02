<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnyhwpbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnyhwpbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:run-treadmill-line" {...props}></Icon>
