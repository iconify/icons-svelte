<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsvpsrbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nsvpsrbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:sort-amount-up" {...props}></Icon>
