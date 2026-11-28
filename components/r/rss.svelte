<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbkosfbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbkosfbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:rss" {...props}></Icon>
