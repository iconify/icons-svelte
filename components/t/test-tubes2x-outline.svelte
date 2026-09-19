<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whemcl2nf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="whemcl2nf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:test-tubes2x-outline" {...props}></Icon>
