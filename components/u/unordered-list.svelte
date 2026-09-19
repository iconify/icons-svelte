<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka-34xg_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ka-34xg_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:unordered-list" {...props}></Icon>
