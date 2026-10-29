<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo_9irb0d.css';
import '../../css/l/l6wodwbos.css';
import '../../css/s/siajtsbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo_9irb0d"/><path class="l6wodwbos"/><path class="siajtsbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:wrench" {...props}></Icon>
