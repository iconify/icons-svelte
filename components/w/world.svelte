<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzjdr7-si.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzjdr7-si"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:world" {...props}></Icon>
