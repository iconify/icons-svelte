<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-39wdb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-39wdb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:search-alt" {...props}></Icon>
