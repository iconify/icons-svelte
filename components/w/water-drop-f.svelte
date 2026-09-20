<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq_5smh8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-1.5};
const content = `<path class="tq_5smh8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:water-drop-f" {...props}></Icon>
