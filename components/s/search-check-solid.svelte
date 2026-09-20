<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo71hibdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo71hibdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:search-check-solid" {...props}></Icon>
