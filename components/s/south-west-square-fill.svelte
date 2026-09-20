<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xef9d_vbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xef9d_vbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:south-west-square-fill" {...props}></Icon>
