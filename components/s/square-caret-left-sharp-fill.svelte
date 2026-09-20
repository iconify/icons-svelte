<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztc6p5fos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ztc6p5fos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-caret-left-sharp-fill" {...props}></Icon>
