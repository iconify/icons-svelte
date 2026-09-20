<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apgf6wjmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apgf6wjmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:th-menu-outline" {...props}></Icon>
