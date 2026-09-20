<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz3rlt3dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nz3rlt3dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:watch3" {...props}></Icon>
