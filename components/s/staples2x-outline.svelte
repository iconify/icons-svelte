<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgd5etdai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kgd5etdai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:staples2x-outline" {...props}></Icon>
