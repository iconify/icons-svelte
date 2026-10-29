<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa7yxxbyz.css';
import '../../css/o/oa3dzxuun.css';
import '../../css/f/f-planbwl.css';
import '../../css/o/o3a8pcdop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa7yxxbyz wm-k"/><path class="oa3dzxuun wm-k"/><path class="f-planbwl wm-a"/><path class="o3a8pcdop wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:terminal" {...props}></Icon>
