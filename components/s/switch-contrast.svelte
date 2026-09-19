<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arm89gb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="arm89gb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:switch-contrast" {...props}></Icon>
