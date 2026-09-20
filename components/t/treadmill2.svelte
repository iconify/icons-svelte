<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohpm96byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ohpm96byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:treadmill2" {...props}></Icon>
