<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzfm97b4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fzfm97b4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signal-high-48" {...props}></Icon>
