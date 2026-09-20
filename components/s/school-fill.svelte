<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxii4nblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pxii4nblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:school-fill" {...props}></Icon>
