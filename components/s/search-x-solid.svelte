<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdxr_pmzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdxr_pmzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:search-x-solid" {...props}></Icon>
