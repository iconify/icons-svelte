<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3_8fkw7e.css';
import '../../css/n/n6sk80bgi.css';
import '../../css/i/iy4ux6kpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o3_8fkw7e"/><path clip-rule="evenodd" class="n6sk80bgi"/><path class="iy4ux6kpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sunrise-bold" {...props}></Icon>
