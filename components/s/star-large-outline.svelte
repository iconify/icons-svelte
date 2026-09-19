<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg69hcbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lg69hcbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:star-large-outline" {...props}></Icon>
