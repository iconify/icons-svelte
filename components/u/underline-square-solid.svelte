<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbbc3-_rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lbbc3-_rw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:underline-square-solid" {...props}></Icon>
