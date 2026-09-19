<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0jkpabal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0jkpabal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:snapchat" {...props}></Icon>
