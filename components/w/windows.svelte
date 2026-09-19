<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd0hveb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd0hveb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:windows" {...props}></Icon>
