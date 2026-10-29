<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynpsrlbdk.css';
import '../../css/u/umcjjfb3i.css';
import '../../css/e/evrpsqb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynpsrlbdk"/><path class="umcjjfb3i"/><path class="evrpsqb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:signpost" {...props}></Icon>
