<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxhvmirsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxhvmirsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:table-lamp-01" {...props}></Icon>
