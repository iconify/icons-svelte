<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq4gaac2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq4gaac2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-list-sharp" {...props}></Icon>
