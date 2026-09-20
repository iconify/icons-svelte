<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp5uv_k8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sp5uv_k8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:stool" {...props}></Icon>
