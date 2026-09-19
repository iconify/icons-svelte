<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep5hu0tam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep5hu0tam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:turbolinux" {...props}></Icon>
