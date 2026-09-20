<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohiyfcbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ohiyfcbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:scissors-square-filled" {...props}></Icon>
