<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv5zpjb7q.css';
import '../../css/z/zpye_6bpo.css';
import '../../css/c/cq1cnpxnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nv5zpjb7q"/><path class="zpye_6bpo"/><path class="cq1cnpxnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:vento" {...props}></Icon>
