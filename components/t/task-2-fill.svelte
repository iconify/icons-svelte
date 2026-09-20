<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udxzoccke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udxzoccke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:task-2-fill" {...props}></Icon>
