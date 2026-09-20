<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at8qymb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="at8qymb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:text-search-variant" {...props}></Icon>
