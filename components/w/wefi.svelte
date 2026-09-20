<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_x3yq_dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_x3yq_dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wefi" {...props}></Icon>
