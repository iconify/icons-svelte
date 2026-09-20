<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhcj01g8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhcj01g8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:strategy-tasks-solid" {...props}></Icon>
