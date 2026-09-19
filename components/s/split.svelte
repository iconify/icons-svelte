<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzjr5cb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzjr5cb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:split" {...props}></Icon>
