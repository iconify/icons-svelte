<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es0fyfvbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es0fyfvbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:user-exclamation" {...props}></Icon>
