<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um232xbll.css';
import '../../css/k/k77-kcbrm.css';
import '../../css/k/k9qkfnbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="um232xbll"/><path class="k77-kcbrm"/><path class="k9qkfnbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:text-size-48" {...props}></Icon>
