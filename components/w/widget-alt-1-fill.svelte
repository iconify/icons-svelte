<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv8r3jb8z.css';
import '../../css/m/m-whd2b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv8r3jb8z"/><path clip-rule="evenodd" class="m-whd2b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:widget-alt-1-fill" {...props}></Icon>
