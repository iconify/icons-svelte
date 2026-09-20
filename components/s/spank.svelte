<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urgyh8mug.css';
import '../../css/g/gx_3x244w.css';
import '../../css/y/y4nqx7dgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urgyh8mug"/><path class="gx_3x244w"/><path class="y4nqx7dgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:spank" {...props}></Icon>
