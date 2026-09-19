<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efozn8miw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efozn8miw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:zoom-out" {...props}></Icon>
