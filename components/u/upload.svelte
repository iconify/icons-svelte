<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkn4hp0vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkn4hp0vr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:upload" {...props}></Icon>
