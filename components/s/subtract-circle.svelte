<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc41xub6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc41xub6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:subtract-circle" {...props}></Icon>
