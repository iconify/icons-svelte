<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh_qdbcvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh_qdbcvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:search-plus-solid" {...props}></Icon>
