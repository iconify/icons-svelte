<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdgv0f7nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdgv0f7nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-search-filled" {...props}></Icon>
