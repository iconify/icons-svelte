<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pln8hgj9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pln8hgj9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:search-slash" {...props}></Icon>
