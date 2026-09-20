<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzd_86c9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzd_86c9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:skull-2-fill" {...props}></Icon>
