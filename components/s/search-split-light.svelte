<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d01g2lbqs.css';
import '../../css/i/ijt9r4b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d01g2lbqs"/><path class="ijt9r4b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:search-split-light" {...props}></Icon>
