<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egs3wlbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egs3wlbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-edit-fill" {...props}></Icon>
